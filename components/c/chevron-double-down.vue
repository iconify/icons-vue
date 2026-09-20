<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/r/rb1yuy.css';
import '../../css/m/mq2u7y.css';
import '../../css/s/so-from-12.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c rb1yuy"/><path class="a0m25c mq2u7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:chevron-double-down" /></template>
