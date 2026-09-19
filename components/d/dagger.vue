<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_zilyvrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="v_zilyvrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:dagger" /></template>
