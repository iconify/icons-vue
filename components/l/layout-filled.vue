<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhbvqjyxk.css';
import '../../css/j/j64dr1bxs.css';
import '../../css/g/gtn46m-jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="bhbvqjyxk"/><rect class="j64dr1bxs"/><rect class="gtn46m-jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:layout-filled" /></template>
