<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zirnvx3hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lingerie-department" /></template>
<style>
.zirnvx3hm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 11.555q-1.108-2.518-3.852-2.776l-.907-5.893q-.022-.147-.1-.275q-.077-.128-.197-.216t-.266-.123q-.145-.036-.292-.013q-.073.011-.142.036q-.07.025-.133.064q-.063.038-.118.088t-.098.109q-.043.06-.075.127q-.031.067-.048.139q-.018.071-.021.145t.008.147l.875 5.69q-4.36.568-4.384 7.122q-.5.559-.5 1.324q0 2 2 2h16.5q2 0 2-2q0-1.002-.502-1.502q-.082-6.384-4.382-6.944l.875-5.69q.012-.073.008-.147q-.003-.074-.021-.145q-.017-.072-.048-.139q-.032-.067-.075-.127q-.044-.059-.098-.109t-.118-.088q-.063-.039-.133-.064q-.069-.025-.142-.036q-.147-.023-.292.013t-.266.123t-.197.216q-.078.128-.1.275l-.907 5.893q-2.744.258-3.852 2.776M7.5 10.25q3.497 0 3.733 5H3.767q.236-5 3.733-5m9 0q3.497 0 3.733 5h-7.466q.236-5 3.733-5");
}

</style>
