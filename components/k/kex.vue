<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x24otrb4s.css';
import '../../css/s/s5a3cqb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x24otrb4s"/><path class="s5a3cqb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kex" /></template>
