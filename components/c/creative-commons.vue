<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0zte_ban.css';
import '../../css/u/u_7efpbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a0zte_ban"/><path class="u_7efpbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:creative-commons" /></template>
