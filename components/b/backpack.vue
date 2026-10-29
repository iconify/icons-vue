<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jarc6s6ki.css';
import '../../css/s/sh9y-3b-t.css';
import '../../css/a/anpv6btnk.css';
import '../../css/j/jxw8_1b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jarc6s6ki wm-k"/><path class="sh9y-3b-t wm-k"/><path class="anpv6btnk wm-a"/><path class="jxw8_1b8y wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:backpack" /></template>
