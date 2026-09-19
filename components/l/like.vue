<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udrs8xbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udrs8xbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:like" /></template>
