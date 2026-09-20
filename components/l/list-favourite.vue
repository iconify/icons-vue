<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqp03tuhu.css';
import '../../css/h/htn9lvbbo.css';
import '../../css/f/fbzxk2bxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="lqp03tuhu"/><path class="htn9lvbbo"/><path class="fbzxk2bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:list-favourite" /></template>
