<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi_la0bqj.css';
import '../../css/v/vf3vx-b1v.css';
import '../../css/a/a1xbh8u7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="vi_la0bqj"/><path class="vf3vx-b1v"/><path class="a1xbh8u7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:email-unread" /></template>
