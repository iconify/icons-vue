<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzij4vhun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrows-up-down-circle-outline-rounded" /></template>
<style>
.dzij4vhun {
  fill: currentColor;
  d: path("M8.1 21.213q-1.825-.788-3.175-2.138T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22t-3.9-.788M12 20q3.325 0 5.663-2.337T20 12t-2.337-5.663T12 4T6.337 6.338T4 12t2.338 5.663T12 20m-1-5.3l-.9-.9q-.275-.275-.7-.275t-.7.275t-.275.7t.275.7l2.6 2.6q.3.3.7.3t.7-.3l2.6-2.6q.275-.275.275-.7t-.275-.7t-.7-.275t-.7.275l-.9.9V9.3l.9.9q.275.275.7.275t.7-.275t.275-.7t-.275-.7l-2.6-2.6q-.3-.3-.7-.3t-.7.3L8.7 8.8q-.275.275-.275.7t.275.7t.7.275t.7-.275l.9-.9z");
}

</style>
