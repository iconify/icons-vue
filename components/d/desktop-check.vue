<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8dem8bar.css';
import '../../css/g/gyqp2acas.css';
import '../../css/j/jvoh6cbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t8dem8bar"/><path clip-rule="evenodd" class="gyqp2acas"/><path class="jvoh6cbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:desktop-check" /></template>
