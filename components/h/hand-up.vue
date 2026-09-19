<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9y9qbl1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9y9qbl1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:hand-up" /></template>
