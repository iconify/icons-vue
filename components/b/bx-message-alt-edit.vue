<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snfofybnw.css';
import '../../css/e/e6l3g5bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snfofybnw"/><path class="e6l3g5bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-message-alt-edit" /></template>
