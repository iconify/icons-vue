<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9rq_swmq.css';
import '../../css/b/bhcwjtbdh.css';
import '../../css/y/y-ulyzb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q9rq_swmq"/><path class="bhcwjtbdh"/><path class="y-ulyzb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:balloon-outline" /></template>
