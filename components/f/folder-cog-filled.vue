<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-64gvbsn.css';
import '../../css/p/pb7wd1b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-64gvbsn"/><path class="pb7wd1b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:folder-cog-filled" /></template>
