<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qseawcbxu.css';
import '../../css/v/v_f8rsa0h.css';
import '../../css/v/vwzrdlbul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qseawcbxu"/><circle class="v_f8rsa0h"/><path class="vwzrdlbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-photo-album" /></template>
