<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbvv7mb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="mbvv7mb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:brush" /></template>
