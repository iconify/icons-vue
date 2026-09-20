<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoy2yqb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eoy2yqb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bulwark-light" /></template>
