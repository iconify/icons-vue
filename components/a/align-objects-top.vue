<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4ijzfbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n4ijzfbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:align-objects-top" /></template>
