<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb2xhv94q.css';
import '../../css/r/r-fuctb7v.css';
import '../../css/y/y8gsoobat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fb2xhv94q"/><path class="r-fuctb7v"/><path class="y8gsoobat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:history" /></template>
