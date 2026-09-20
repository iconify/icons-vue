<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuur59v_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zuur59v_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:castle-alt-1-fill" /></template>
