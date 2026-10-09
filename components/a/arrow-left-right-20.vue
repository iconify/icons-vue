<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ritkb0p_x.css';
import '../../css/w/wp6vfybzd.css';
import '../../css/j/jgrjg5bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ritkb0p_x"/><path class="wp6vfybzd"/><path class="jgrjg5bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-left-right-20" /></template>
