<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8tn4t_cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="b8tn4t_cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:discord-alt" /></template>
