<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zavz-4t8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zavz-4t8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hyperhdr-light" /></template>
