<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmwojzuep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmwojzuep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:briefcase-alt-filled" /></template>
