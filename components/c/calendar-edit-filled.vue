<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/biyv__4lr.css';
import '../../css/f/f_fvtdbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="biyv__4lr"/><path class="f_fvtdbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:calendar-edit-filled" /></template>
