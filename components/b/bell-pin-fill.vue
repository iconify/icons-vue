<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp39-b6it.css';
import '../../css/f/f72i5tbxt.css';
import '../../css/k/kl2jsebar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xp39-b6it"/><path class="f72i5tbxt"/><circle class="kl2jsebar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:bell-pin-fill" /></template>
