<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7uwmjy0t.css';
import '../../css/m/mg-6g4b_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7uwmjy0t"/><path class="mg-6g4b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:inbox-star-fill" /></template>
