<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7r-7tw7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7r-7tw7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:less-than" /></template>
