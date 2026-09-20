<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8w3rabjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8w3rabjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:info-circle-solid" /></template>
