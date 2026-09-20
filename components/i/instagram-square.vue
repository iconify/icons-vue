<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzle1mbxg.css';
import '../../css/m/mzxakcc6v.css';
import '../../css/a/a0i4ueb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzle1mbxg"/><path class="mzxakcc6v"/><path class="a0i4ueb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:instagram-square" /></template>
