<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_a1kp80n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ball-curve" /></template>
<style>
.c_a1kp80n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.288 3.788Q10.75 5.325 10.75 7.5t1.538 3.712Q13.825 12.75 16 12.75t3.712-1.538Q21.25 9.675 21.25 7.5t-1.538-3.712Q18.175 2.25 16 2.25t-3.712 1.538m-6.813 15.15q-.717 1.16-3.025 1.314q-.149.01-.282.076q-.134.066-.232.178q-.099.112-.146.254q-.048.141-.038.29q.005.074.024.145t.052.137t.077.125q.046.059.101.107q.056.049.12.086t.134.06t.143.034q.073.009.147.004q4.711-.314 4.975-5.511q.161-3.145 2.109-3.499q.073-.013.142-.04t.13-.068q.062-.04.116-.091q.053-.051.095-.112t.071-.129t.045-.14t.017-.146t-.012-.146t-.04-.142q-.028-.068-.068-.13t-.091-.116t-.112-.095t-.129-.071t-.14-.045t-.146-.017t-.146.012q-3.118.567-3.339 4.899q-.104 2.053-.552 2.777");
}

</style>
