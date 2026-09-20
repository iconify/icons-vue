<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7uq3ghml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q7uq3ghml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bitbucket-outline" /></template>
