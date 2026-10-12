<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2c8qbzit.css';
import '../../css/v/vux-2mbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2c8qbzit"/><path class="vux-2mbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-chevrons-right-filled" /></template>
