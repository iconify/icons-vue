<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xckdb_rmw.css';
import '../../css/d/dau5oxg5b.css';
import '../../css/y/yufc7rbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xckdb_rmw"/><path class="dau5oxg5b"/><path class="yufc7rbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-archive-filled" /></template>
