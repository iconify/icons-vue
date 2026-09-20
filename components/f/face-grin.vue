<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txfzqa3vh.css';
import '../../css/o/ooafjrbnh.css';
import '../../css/m/mqpsn0bso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txfzqa3vh"/><path class="ooafjrbnh"/><path class="mqpsn0bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:face-grin" /></template>
