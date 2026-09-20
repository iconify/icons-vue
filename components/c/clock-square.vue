<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1gg4qb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v1gg4qb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:clock-square" /></template>
