<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwkbxxb3f.css';
import '../../css/f/fkq9d_i7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwkbxxb3f"/><path class="fkq9d_i7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:history" /></template>
