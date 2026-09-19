<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbvjsy3py.css';
import '../../css/i/iun2kcife.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tbvjsy3py"/><path class="iun2kcife"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:bug-filled" /></template>
