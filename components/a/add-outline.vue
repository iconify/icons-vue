<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6crs6blw.css';
import '../../css/b/buewkbcgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6crs6blw"/><path clip-rule="evenodd" class="buewkbcgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:add-outline" /></template>
