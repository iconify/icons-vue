<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zml4mvy9b.css';
import '../../css/g/gertnpb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zml4mvy9b"/><path class="gertnpb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:arrow-down" /></template>
