<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwe1oubqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwe1oubqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:codestream" /></template>
