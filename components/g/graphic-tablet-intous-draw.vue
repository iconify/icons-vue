<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xopt6g09k.css';
import '../../css/m/m4mtarblb.css';
import '../../css/e/e36jr6zuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xopt6g09k"/><path class="m4mtarblb"/><path class="e36jr6zuj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:graphic-tablet-intous-draw" /></template>
