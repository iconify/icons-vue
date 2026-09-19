<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dskmdxbel.css';
import '../../css/z/z0k1ug9bx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dskmdxbel"/><path class="z0k1ug9bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cabinet" /></template>
