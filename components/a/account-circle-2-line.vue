<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft6fc1ajc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft6fc1ajc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:account-circle-2-line" /></template>
