<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo-j0bcdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yo-j0bcdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:branching-paths-up-bold" /></template>
