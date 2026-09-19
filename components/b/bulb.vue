<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwizj5bpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pwizj5bpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:bulb" /></template>
