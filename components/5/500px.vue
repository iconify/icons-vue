<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojriq_b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ojriq_b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:500px" /></template>
