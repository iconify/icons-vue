<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1kkhe1_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1kkhe1_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apache-cordova" /></template>
