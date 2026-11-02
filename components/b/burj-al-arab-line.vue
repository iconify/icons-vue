<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz18w6tjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz18w6tjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:burj-al-arab-line" /></template>
