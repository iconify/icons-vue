<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8i80_bea.css';
import '../../css/u/ua7k7g4ui.css';
import '../../css/a/aiheh3blt.css';
import '../../css/s/switkv-0r.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--alerted clr-i-solid-path-1--alerted p8i80_bea"/><path class="clr-i-solid--alerted clr-i-solid-path-2--alerted ua7k7g4ui"/><path class="aiheh3blt clr-i-solid--alerted clr-i-solid-path-3--alerted"/><path class="clr-i-alert clr-i-solid--alerted clr-i-solid-path-4--alerted switkv-0r"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:computer-solid-alerted" /></template>
