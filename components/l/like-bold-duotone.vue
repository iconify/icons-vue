<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz43omb9k.css';
import '../../css/h/hsrg7muou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qz43omb9k"/><path clip-rule="evenodd" class="hsrg7muou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:like-bold-duotone" /></template>
