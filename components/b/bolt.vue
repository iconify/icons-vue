<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-fk36gkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j-fk36gkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bolt" /></template>
