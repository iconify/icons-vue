<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b133qtshg.css';
import '../../css/j/jbgenzzof.css';
import '../../css/w/wi7o0k21l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b133qtshg"/><path class="jbgenzzof"/><path class="wi7o0k21l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:inbox-unread-bold" /></template>
