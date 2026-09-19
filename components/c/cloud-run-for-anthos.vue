<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hec1o9hrf.css';
import '../../css/a/ablh-jbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hec1o9hrf"/><path class="ablh-jbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:cloud-run-for-anthos" /></template>
