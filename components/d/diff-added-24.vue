<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stu8cqb7t.css';
import '../../css/c/c485hsbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stu8cqb7t"/><path class="c485hsbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:diff-added-24" /></template>
