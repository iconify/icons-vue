<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw53xhb4q.css';
import '../../css/s/s0u7hix8w.css';
import '../../css/r/rg3j4qb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bw53xhb4q"/><path class="s0u7hix8w"/><path class="rg3j4qb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-large-bold" /></template>
