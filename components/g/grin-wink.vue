<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia_eumbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="ia_eumbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:grin-wink" /></template>
