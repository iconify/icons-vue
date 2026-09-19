<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pjdkm-3dm.css';
import '../../css/o/o11ck2bjj.css';
import '../../css/v/v3miwabnt.css';
import '../../css/q/qokknfbsn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhI3xJb7u"><g class="ft5dv1b6b"><path class="pjdkm-3dm"/><path class="o11ck2bjj"/><circle class="v3miwabnt"/><path class="qokknfbsn"/></g></mask></defs><path mask="url(#SVGhI3xJb7u)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:blade" /></template>
