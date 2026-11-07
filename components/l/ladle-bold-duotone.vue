<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo5hu07_i.css';
import '../../css/s/s7zqjx21v.css';
import '../../css/n/nyn8xjb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo5hu07_i"/><path class="s7zqjx21v"/><path class="nyn8xjb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ladle-bold-duotone" /></template>
