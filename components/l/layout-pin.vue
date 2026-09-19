<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_m_r1b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b_m_r1b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:layout-pin" /></template>
