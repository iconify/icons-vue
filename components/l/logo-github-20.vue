<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlh7a3iac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wlh7a3iac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:logo-github-20" /></template>
