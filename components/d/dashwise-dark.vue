<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as7t9kaju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="as7t9kaju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dashwise-dark" /></template>
