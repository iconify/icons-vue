<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o63iyfbss.css';
import '../../css/t/tmavxu-df.css';
import '../../css/u/u7fpslg-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o63iyfbss"/><path class="tmavxu-df"/><path class="u7fpslg-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-burner-20" /></template>
