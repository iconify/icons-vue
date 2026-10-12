<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zain2eb2r.css';
import '../../css/s/sk4ad7b3f.css';
import '../../css/z/zkdyo_ief.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zain2eb2r"/><path class="sk4ad7b3f"/><path class="zkdyo_ief"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-minus-20" /></template>
