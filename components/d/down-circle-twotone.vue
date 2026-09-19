<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si4d4hb_u.css';
import '../../css/y/yv_brepse.css';
import '../../css/f/f33c5bbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="si4d4hb_u"/><path class="yv_brepse"/><path class="f33c5bbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:down-circle-twotone" /></template>
