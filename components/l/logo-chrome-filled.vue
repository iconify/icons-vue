<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de11cjbha.css';
import '../../css/h/hj5-87b9h.css';
import '../../css/t/tefo83bja.css';
import '../../css/g/gtksz7byo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de11cjbha"/><path class="hj5-87b9h"/><path class="tefo83bja"/><path class="gtksz7byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-chrome-filled" /></template>
