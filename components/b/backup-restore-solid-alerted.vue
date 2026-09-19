<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi3ijvhgu.css';
import '../../css/t/tv4fd-brp.css';
import '../../css/g/giczhqb6w.css';
import '../../css/s/switkv-0r.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--alerted clr-i-solid-path-1--alerted xi3ijvhgu"/><path class="clr-i-solid--alerted clr-i-solid-path-2--alerted tv4fd-brp"/><path class="clr-i-solid--alerted clr-i-solid-path-3--alerted giczhqb6w"/><path class="clr-i-alert clr-i-solid--alerted clr-i-solid-path-4--alerted switkv-0r"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:backup-restore-solid-alerted" /></template>
