<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acjh3nbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acjh3nbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:chocolatey" /></template>
