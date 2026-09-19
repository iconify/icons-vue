<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p20oifbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p20oifbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:git-fork" /></template>
