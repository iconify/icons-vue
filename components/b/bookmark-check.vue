<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su66_gbtt.css';
import '../../css/f/fmqud68ht.css';
import '../../css/i/i28wl7b4q.css';
import '../../css/n/np9kj11rx.css';
import '../../css/s/syqas2b4c.css';
import '../../css/v/vxciwfbpw.css';
import '../../css/q/qwtciubfr.css';
import '../../css/h/hxu2lhkgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="su66_gbtt wm-shadow"/><path class="fmqud68ht wm-k"/><path class="i28wl7b4q wm-k"/><path class="np9kj11rx wm-k"/><path class="syqas2b4c wm-k"/><path class="vxciwfbpw wm-k"/><path class="qwtciubfr wm-shine"/><path class="hxu2lhkgi wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:bookmark-check" /></template>
