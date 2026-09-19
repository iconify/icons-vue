<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0v9jjbyk.css';
import '../../css/x/x3ykjurxz.css';
import '../../css/c/czxvcbrup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r0v9jjbyk"/><path class="x3ykjurxz"/><path class="czxvcbrup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:behance2" /></template>
