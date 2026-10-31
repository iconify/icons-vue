<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj9cgxb4q.css';
import '../../css/w/wprsklb5k.css';
import '../../css/b/bupxdcvvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="rj9cgxb4q"/><path class="wprsklb5k"/><path class="bupxdcvvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:bulgaria" /></template>
