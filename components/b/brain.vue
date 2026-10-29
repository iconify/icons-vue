<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_1j10-np.css';
import '../../css/r/r2nonpb-r.css';
import '../../css/l/lhyk42bxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_1j10-np wm-a"/><path class="r2nonpb-r wm-a"/><path class="lhyk42bxl wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:brain" /></template>
