<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii0_g0bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii0_g0bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:flask-conical" /></template>
