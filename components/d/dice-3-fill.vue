<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi94q_tnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gi94q_tnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dice-3-fill" /></template>
