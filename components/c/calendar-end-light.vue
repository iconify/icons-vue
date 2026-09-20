<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odnhlrb0v.css';
import '../../css/y/ynooprbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odnhlrb0v"/><path class="ynooprbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:calendar-end-light" /></template>
