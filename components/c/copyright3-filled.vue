<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6yze_b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6yze_b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:copyright3-filled" /></template>
