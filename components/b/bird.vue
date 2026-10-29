<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rouolwb-f.css';
import '../../css/p/p_159wb4v.css';
import '../../css/e/ejsy3vbgl.css';
import '../../css/r/r3jjc7baz.css';
import '../../css/z/zdzaeezkn.css';
import '../../css/v/vnt-9cc-b.css';
import '../../css/i/ihsmntttp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rouolwb-f wm-a"/><path class="p_159wb4v wm-k"/><path class="ejsy3vbgl wm-k"/><path class="r3jjc7baz wm-k"/><path class="wm-k zdzaeezkn"/><path class="vnt-9cc-b wm-a"/><path class="ihsmntttp wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:bird" /></template>
