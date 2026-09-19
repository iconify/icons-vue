<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/begoqnbqd.css';
import '../../css/x/xwizttm5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="begoqnbqd"/><path class="xwizttm5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chess-knight" /></template>
