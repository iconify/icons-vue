<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoq8jmbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cable-tv" /></template>
<style>
.aoq8jmbil {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.064 2.506L10 5.861l2.936-3.355q.098-.112.232-.178q.133-.066.282-.076t.29.038q.142.047.254.146q.055.048.101.107q.045.058.077.125q.033.066.052.137t.024.145t-.004.147q-.01.073-.034.143q-.023.07-.06.134t-.086.12L11.653 6.25H14q1.76 0 3.005 1.245T18.25 10.5v1.25H19q2.25 0 2.25 2.25v3.826q1.5.337 1.5 2.174q0 2.25-2.25 2.25T18.25 20q0-1.837 1.5-2.174V14q0-.75-.75-.75h-.75v1.25q0 1.76-1.245 3.005T14 18.75H6q-1.76 0-3.005-1.245T1.75 14.5v-4q0-1.76 1.245-3.005T6 6.25h2.347L5.936 3.494q-.049-.056-.086-.12t-.06-.134q-.024-.07-.034-.143q-.009-.073-.004-.147t.024-.145t.052-.137q.032-.067.077-.125q.046-.059.101-.107q.112-.099.254-.146q.141-.048.29-.038t.282.076q.134.066.232.178");
}

</style>
