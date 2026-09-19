<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy-mau2gx.css';
import '../../css/h/huruoib_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b gy-mau2gx"/><path class="b huruoib_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:gumroad" /></template>
