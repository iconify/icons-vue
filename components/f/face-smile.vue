<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9kl2ncoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q9kl2ncoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-smile" /></template>
