<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj81zpj-r.css';
import '../../css/n/nm_4mya7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bj81zpj-r"/><path class="nm_4mya7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:balloon" /></template>
