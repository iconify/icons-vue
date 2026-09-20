<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6i__zbof.css';
import '../../css/t/th5wqpzfa.css';
import '../../css/q/qfnkoxw6w.css';
import '../../css/i/i6jalmb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6i__zbof"/><path clip-rule="evenodd" class="th5wqpzfa"/><path clip-rule="evenodd" class="qfnkoxw6w"/><path class="i6jalmb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:desktop-check-duotone" /></template>
