<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3x112bdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3x112bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:datalab" /></template>
