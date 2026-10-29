<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzgeyjwmg.css';
import '../../css/r/r0i2nmbpf.css';
import '../../css/r/rdv65ibcl.css';
import '../../css/a/ajlu13b3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzgeyjwmg wm-k"/><path class="r0i2nmbpf wm-k"/><path class="rdv65ibcl wm-k"/><path class="ajlu13b3x wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:layout-template" /></template>
