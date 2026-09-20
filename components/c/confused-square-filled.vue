<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et_gkj67v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="et_gkj67v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:confused-square-filled" /></template>
