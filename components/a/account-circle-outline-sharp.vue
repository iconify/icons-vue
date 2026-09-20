<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g964c8l1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:account-circle-outline-sharp" /></template>
<style>
.g964c8l1q {
  fill: currentColor;
  d: path("M6.196 17.485q1.275-.918 2.706-1.451Q10.332 15.5 12 15.5t3.098.534t2.706 1.45q.99-1.025 1.593-2.42Q20 13.667 20 12q0-3.325-2.337-5.663T12 4T6.337 6.338T4 12q0 1.667.603 3.064q.603 1.396 1.593 2.42m3.672-5.852Q9 10.764 9 9.5t.868-2.132T12 6.5t2.132.868T15 9.5t-.868 2.132T12 12.5t-2.132-.868M12 21q-1.883 0-3.525-.701t-2.858-1.916t-1.916-2.858T3 12t.701-3.525t1.916-2.858q1.216-1.215 2.858-1.916T12 3t3.525.701t2.858 1.916t1.916 2.858T21 12t-.701 3.525t-1.916 2.858q-1.216 1.215-2.858 1.916T12 21m2.721-1.484q1.338-.483 2.313-1.324q-.974-.783-2.255-1.237T12 16.5t-2.789.445t-2.246 1.247q.975.84 2.314 1.324T12 20t2.721-.484m-1.3-8.595Q14 10.342 14 9.5t-.579-1.421T12 7.5t-1.421.579T10 9.5t.579 1.421T12 11.5t1.421-.579M12 18.25");
}

</style>
