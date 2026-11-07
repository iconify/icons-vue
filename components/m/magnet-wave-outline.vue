<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_i-7bb7z.css';
import '../../css/o/o3283cgee.css';
import '../../css/k/kjo9alciz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v_i-7bb7z"/><path class="o3283cgee"/><path class="kjo9alciz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnet-wave-outline" /></template>
