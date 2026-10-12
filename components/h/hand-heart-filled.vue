<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkvx_ob1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xkvx_ob1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hand-heart-filled" /></template>
