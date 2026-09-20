<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urxzsob5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urxzsob5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ghost-2-filled" /></template>
