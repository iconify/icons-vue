<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muotlpbym.css';
import '../../css/w/ws98rr2bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muotlpbym"/><path clip-rule="evenodd" class="ws98rr2bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:boom-box-filled" /></template>
