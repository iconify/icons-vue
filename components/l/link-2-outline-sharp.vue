<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxwau_70b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:link-2-outline-sharp" /></template>
<style>
.hxwau_70b {
  fill: currentColor;
  d: path("M8.2 20q-1.742 0-2.971-1.229T4 15.8q0-.846.308-1.611q.308-.766.911-1.37l3.023-2.998l.708.708l-3.023 3.004q-.463.463-.705 1.049T4.981 15.8q0 1.34.94 2.27Q6.86 19 8.2 19q.633 0 1.221-.241q.589-.242 1.052-.705l3.018-3.004l.713.714l-3.023 2.998q-.604.604-1.37.92Q9.047 20 8.2 20m1.84-5.346l-.694-.714l4.614-4.613l.713.713zm5.718-.47l-.708-.693l3.023-3.018q.444-.444.683-1.017t.238-1.206q0-1.346-.936-2.298Q17.12 5 15.775 5q-.633 0-1.218.241q-.586.242-1.03.686L10.51 8.95l-.694-.708l3.003-3.004q.604-.604 1.37-.92Q14.954 4 15.8 4q1.742 0 2.968 1.239t1.226 2.986q0 .84-.304 1.596q-.305.756-.91 1.36z");
}

</style>
