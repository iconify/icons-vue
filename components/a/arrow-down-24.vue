<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmje_kq9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmje_kq9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-down-24" /></template>
