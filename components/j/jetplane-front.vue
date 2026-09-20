<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7c_9fb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v7c_9fb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:jetplane-front" /></template>
