<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8o2xibod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8o2xibod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:dependencycheck" /></template>
