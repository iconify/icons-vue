<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwun26bcz.css';
import '../../css/b/buzpo8b_c.css';
import '../../css/y/yayoa0eev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zwun26bcz"/><path class="buzpo8b_c"/><path class="yayoa0eev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:jack-up-vessel-48-bold" /></template>
