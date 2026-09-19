<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6_5uh8cp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b6_5uh8cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:erase" /></template>
