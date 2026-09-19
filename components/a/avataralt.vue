<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6l3-xb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="h6l3-xb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:avataralt" /></template>
