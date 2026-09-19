<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqlclbcvx.css';
import '../../css/g/g5j-hk_bn.css';
import '../../css/t/tw5kz9gbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="eqlclbcvx"/><path class="g5j-hk_bn"/><path class="tw5kz9gbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:comment" /></template>
