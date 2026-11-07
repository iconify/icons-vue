<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7ses8b9s.css';
import '../../css/s/su9n4xbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7ses8b9s"/><path clip-rule="evenodd" class="su9n4xbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:key-minimalistic-square-2-bold" /></template>
