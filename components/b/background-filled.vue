<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_2l-mb5b.css';
import '../../css/b/b5_hbpb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_2l-mb5b"/><path class="b5_hbpb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:background-filled" /></template>
