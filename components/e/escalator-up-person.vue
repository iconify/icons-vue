<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_iv7cbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_iv7cbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:escalator-up-person" /></template>
