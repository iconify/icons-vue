<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szb27ezbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szb27ezbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:eye-closed-24" /></template>
